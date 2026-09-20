<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d86fmyhpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d86fmyhpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:cloud-download" /></template>
