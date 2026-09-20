<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlkplcb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vlkplcb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:inspire-square" /></template>
