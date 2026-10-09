<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2jt75bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d2jt75bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-footprint-48-bold" /></template>
