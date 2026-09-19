<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9zf29bpy.css';
import '../../css/t/tcyc0_hyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a9zf29bpy"/><path class="tcyc0_hyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bar" /></template>
