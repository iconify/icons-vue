<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfbuh_-3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pfbuh_-3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:greensock" /></template>
