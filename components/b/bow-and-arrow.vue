<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m64zwy8rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m64zwy8rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bow-and-arrow" /></template>
