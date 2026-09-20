<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soayfe2qc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="soayfe2qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:compass-rose-in-circle-outline" /></template>
