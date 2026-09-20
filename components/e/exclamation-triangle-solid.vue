<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubzib6b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ubzib6b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:exclamation-triangle-solid" /></template>
