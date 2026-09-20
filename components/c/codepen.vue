<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk3dtpmsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nk3dtpmsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:codepen" /></template>
