<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwf2drwlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hwf2drwlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-top-left" /></template>
