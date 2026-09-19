<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppq9iy35x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ppq9iy35x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:linux" /></template>
