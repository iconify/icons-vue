<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf439884l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hf439884l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:head-side-virus" /></template>
