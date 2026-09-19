<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzmb8kc6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="gzmb8kc6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:blender" /></template>
