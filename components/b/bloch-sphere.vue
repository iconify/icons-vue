<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_vg3tb-o.css';
import '../../css/w/w8xuifbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p_vg3tb-o"/><path class="w8xuifbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bloch-sphere" /></template>
