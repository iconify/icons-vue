<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1nh9mbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o1nh9mbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:flip-horizontal-arrow-1-remix" /></template>
