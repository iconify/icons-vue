<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocssg7g_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ocssg7g_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:bluetooth-b" /></template>
