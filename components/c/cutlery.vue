<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6x4xva_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="x6x4xva_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cutlery" /></template>
