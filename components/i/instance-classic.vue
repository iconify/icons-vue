<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6ros9nur.css';
import '../../css/c/c8kuy_ape.css';
import '../../css/x/xt_a157cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i6ros9nur"/><circle class="c8kuy_ape"/><path class="xt_a157cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:instance-classic" /></template>
