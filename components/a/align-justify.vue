<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjox5-scv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bjox5-scv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:align-justify" /></template>
