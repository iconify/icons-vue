<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug-axbtvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug-axbtvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:calm-1-filled" /></template>
