<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wabg_o55n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wabg_o55n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:generic-sorting-2" /></template>
