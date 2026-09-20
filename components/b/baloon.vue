<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu_ys67gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nu_ys67gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:baloon" /></template>
