<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq57hxbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iq57hxbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cocktail" /></template>
