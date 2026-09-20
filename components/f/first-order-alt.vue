<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_nv4obkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_nv4obkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:first-order-alt" /></template>
