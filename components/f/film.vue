<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkh5wzb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bkh5wzb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:film" /></template>
