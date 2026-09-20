<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf530d1ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf530d1ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:card-plus" /></template>
