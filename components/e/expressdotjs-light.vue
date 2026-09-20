<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4p89lbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w4p89lbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:expressdotjs-light" /></template>
