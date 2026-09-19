<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hota12b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":384};
const content = `<path class="hota12b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:fast-forward" /></template>
