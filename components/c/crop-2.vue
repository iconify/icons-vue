<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r__jeok_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="r__jeok_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:crop-2" /></template>
