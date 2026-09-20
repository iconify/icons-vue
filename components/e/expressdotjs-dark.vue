<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wae55l3tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wae55l3tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:expressdotjs-dark" /></template>
