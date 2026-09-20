<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5mssp-sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y5mssp-sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-in-rectangle-outline" /></template>
