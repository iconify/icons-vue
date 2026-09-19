<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoam0_w_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="xoam0_w_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:coffee" /></template>
