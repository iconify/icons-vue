<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4ti73b2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r4ti73b2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bullet-list" /></template>
