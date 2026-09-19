<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qonqq2zjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qonqq2zjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:copy-stroke-12" /></template>
