<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4_ukxvxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k4_ukxvxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:center-horizontally-filled" /></template>
