<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz6mxm6pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kz6mxm6pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-save" /></template>
