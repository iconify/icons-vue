<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlvo0thnk.css';
import '../../css/i/iih3otspu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vlvo0thnk"/><path class="iih3otspu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watson-machine-learning" /></template>
