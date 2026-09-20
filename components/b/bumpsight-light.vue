<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo9cc-xor.css';
import '../../css/r/rd8e13qsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="eo9cc-xor"/><path class="rd8e13qsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bumpsight-light" /></template>
