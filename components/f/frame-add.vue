<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r42bjtblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r42bjtblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:frame-add" /></template>
