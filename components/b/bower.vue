<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wofw3ubgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wofw3ubgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bower" /></template>
