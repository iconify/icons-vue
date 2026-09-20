<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceecv5bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ceecv5bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:battery4" /></template>
