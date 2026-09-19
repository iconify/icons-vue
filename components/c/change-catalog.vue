<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y21dk_wfs.css';
import '../../css/k/k4mqvjn9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y21dk_wfs"/><path class="k4mqvjn9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:change-catalog" /></template>
