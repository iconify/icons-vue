<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkk768bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dkk768bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clover" /></template>
