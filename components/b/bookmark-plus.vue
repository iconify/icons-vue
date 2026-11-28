<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad5u6q4jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad5u6q4jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bookmark-plus" /></template>
