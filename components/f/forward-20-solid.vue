<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfrv9c1za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yfrv9c1za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:forward-20-solid" /></template>
