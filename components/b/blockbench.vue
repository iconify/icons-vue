<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp4totsei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp4totsei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:blockbench" /></template>
