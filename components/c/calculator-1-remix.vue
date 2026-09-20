<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kny08itgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kny08itgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:calculator-1-remix" /></template>
