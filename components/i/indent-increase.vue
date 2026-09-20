<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3991bcxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="f3991bcxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:indent-increase" /></template>
