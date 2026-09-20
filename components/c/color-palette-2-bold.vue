<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt882wm4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt882wm4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:color-palette-2-bold" /></template>
