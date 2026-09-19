<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osi2d3_5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="osi2d3_5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:close" /></template>
