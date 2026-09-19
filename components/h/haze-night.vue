<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y84bdgn_e.css';
import '../../css/d/dw5u3v8yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y84bdgn_e"/><path class="dw5u3v8yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:haze-night" /></template>
