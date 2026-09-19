<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi2jq6bjc.css';
import '../../css/m/mz86u9bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2jq6bjc"/><path class="mz86u9bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-product-hunt" /></template>
