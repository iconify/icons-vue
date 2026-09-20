<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/matl_strt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="matl_strt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:compsition-horizontal-remix" /></template>
