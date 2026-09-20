<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bivnitf6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bivnitf6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:firefox-fill" /></template>
