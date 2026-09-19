<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aif5mxb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="aif5mxb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:bug" /></template>
