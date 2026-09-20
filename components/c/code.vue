<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqtl5g6pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="nqtl5g6pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code" /></template>
