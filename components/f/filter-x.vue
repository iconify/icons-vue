<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-9kwzbci.css';
import '../../css/l/lh4n09blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-9kwzbci"/><path class="lh4n09blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:filter-x" /></template>
