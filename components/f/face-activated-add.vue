<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftn7tacln.css';
import '../../css/a/am_yeab8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ftn7tacln"/><path class="am_yeab8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-activated-add" /></template>
