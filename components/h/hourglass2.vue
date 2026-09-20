<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxywjfe4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pxywjfe4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass2" /></template>
