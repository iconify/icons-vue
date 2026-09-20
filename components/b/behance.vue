<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c97nk6b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c97nk6b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:behance" /></template>
