<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynjhpt15y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ynjhpt15y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:balance-scale-left" /></template>
