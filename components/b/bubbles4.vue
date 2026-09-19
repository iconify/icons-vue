<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alssx_b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="alssx_b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bubbles4" /></template>
