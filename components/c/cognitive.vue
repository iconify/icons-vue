<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd_z2mmch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jd_z2mmch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cognitive" /></template>
