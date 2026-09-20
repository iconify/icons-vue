<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw4o4cvfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lw4o4cvfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:c" /></template>
