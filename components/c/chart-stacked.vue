<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/seob3mb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="seob3mb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-stacked" /></template>
