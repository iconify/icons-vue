<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwz6_x2lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mwz6_x2lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:dblp" /></template>
