<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxlo_dguu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="pxlo_dguu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:crop" /></template>
