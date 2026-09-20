<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2ys-0kzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="p2ys-0kzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:food" /></template>
