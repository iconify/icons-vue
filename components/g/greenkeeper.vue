<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_48qybps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k_48qybps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:greenkeeper" /></template>
