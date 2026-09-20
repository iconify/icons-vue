<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5c-3sjfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":240};
const content = `<path class="c5c-3sjfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:brevitas" /></template>
