<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4c-fibbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="u4c-fibbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:graph-square" /></template>
