<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsky5lzvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsky5lzvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:itunes" /></template>
