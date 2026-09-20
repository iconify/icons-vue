<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la14y0b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la14y0b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-close-fill" /></template>
