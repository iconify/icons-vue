<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkuwb95yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkuwb95yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-down" /></template>
