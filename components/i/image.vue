<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6v5fxbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y6v5fxbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:image" /></template>
