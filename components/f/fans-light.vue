<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxyf8dbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="hxyf8dbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fans-light" /></template>
