<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd-pldbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wd-pldbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:hashnode" /></template>
