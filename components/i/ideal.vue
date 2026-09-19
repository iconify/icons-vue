<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3d_pybjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u3d_pybjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ideal" /></template>
