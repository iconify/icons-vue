<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbus-_boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="hbus-_boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:list" /></template>
