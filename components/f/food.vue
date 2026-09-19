<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_72i1bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i_72i1bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:food" /></template>
