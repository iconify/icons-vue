<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4h-xeb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k4h-xeb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:archive-box-arrow-down-20-solid" /></template>
