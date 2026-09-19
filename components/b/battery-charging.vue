<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcis7r43e.css';
import '../../css/r/rgfwyacmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xcis7r43e"/><path class="rgfwyacmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:battery-charging" /></template>
