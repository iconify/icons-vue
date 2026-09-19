<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cac5rp0ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="cac5rp0ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dollar-sign" /></template>
