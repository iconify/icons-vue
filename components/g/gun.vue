<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzth97bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pzth97bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:gun" /></template>
