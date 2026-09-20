<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bttzdh-kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bttzdh-kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:checkbox" /></template>
