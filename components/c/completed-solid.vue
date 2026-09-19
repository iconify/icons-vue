<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1z05y-nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w1z05y-nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:completed-solid" /></template>
