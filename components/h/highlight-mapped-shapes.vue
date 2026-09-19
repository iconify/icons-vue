<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu_ffmb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lu_ffmb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:highlight-mapped-shapes" /></template>
