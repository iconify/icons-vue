<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni-6x9bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ni-6x9bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:cloud" /></template>
