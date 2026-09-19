<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8zw34-dy.css';
import '../../css/d/d84_2zbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g8zw34-dy"/><path class="d84_2zbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-npm" /></template>
