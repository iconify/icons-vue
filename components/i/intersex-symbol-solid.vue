<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juaf2_1xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="juaf2_1xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:intersex-symbol-solid" /></template>
