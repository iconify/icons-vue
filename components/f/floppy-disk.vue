<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh_mbgb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fh_mbgb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:floppy-disk" /></template>
