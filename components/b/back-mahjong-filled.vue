<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxmzmm0yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cxmzmm0yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:back-mahjong-filled" /></template>
