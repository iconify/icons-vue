<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k85tt3ajc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="k85tt3ajc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:looks" /></template>
