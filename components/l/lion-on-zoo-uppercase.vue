<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ongxg380j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ongxg380j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lion-on-zoo-uppercase" /></template>
