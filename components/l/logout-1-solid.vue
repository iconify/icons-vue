<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hltb_3h3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hltb_3h3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:logout-1-solid" /></template>
