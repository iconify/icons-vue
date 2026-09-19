<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-uv_2n-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p-uv_2n-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:file-pdf" /></template>
