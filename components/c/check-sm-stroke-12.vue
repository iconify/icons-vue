<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql09f5usd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ql09f5usd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-sm-stroke-12" /></template>
