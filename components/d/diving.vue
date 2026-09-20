<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz3f8bglu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="vz3f8bglu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:diving" /></template>
