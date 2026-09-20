<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl-lx79nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vl-lx79nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:car" /></template>
