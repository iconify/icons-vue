<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi-1inbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zi-1inbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dumpster" /></template>
