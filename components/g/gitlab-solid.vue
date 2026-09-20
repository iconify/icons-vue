<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxw1kfb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxw1kfb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gitlab-solid" /></template>
