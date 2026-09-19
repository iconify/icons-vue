<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h97ie_j_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":656};
const content = `<path class="h97ie_j_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:forward" /></template>
