<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv2u-nbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sv2u-nbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-q" /></template>
