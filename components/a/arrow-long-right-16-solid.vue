<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnn1q3d6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hnn1q3d6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-long-right-16-solid" /></template>
