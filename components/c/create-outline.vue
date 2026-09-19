<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yruwzs0qg.css';
import '../../css/x/xv8czdbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yruwzs0qg"/><path class="xv8czdbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:create-outline" /></template>
