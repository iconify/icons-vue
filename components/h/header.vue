<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8_pid-oz.css';
import '../../css/d/dbej1sbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="dbej1sbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:header" /></template>
