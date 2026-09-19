<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqblwla6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1408};
const content = `<path class="hqblwla6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:check-square-o" /></template>
