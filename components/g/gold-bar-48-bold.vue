<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf6id7bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tf6id7bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gold-bar-48-bold" /></template>
