<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2crndbgo.css';
import '../../css/c/c3jcscciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y2crndbgo"/><path class="c3jcscciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cr-nmaster-light" /></template>
