<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e39vi3inw.css';
import '../../css/t/tpa9noblp.css';
import '../../css/o/ou9bix05e.css';
import '../../css/u/u58babtsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e39vi3inw"/><path class="tpa9noblp"/><path class="ou9bix05e"/><path class="u58babtsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-mq" /></template>
