<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul3dyo2bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul3dyo2bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cut" /></template>
