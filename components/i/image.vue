<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q039x4b1z.css';
import '../../css/v/v32r9rbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q039x4b1z"/><path class="v32r9rbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:image" /></template>
