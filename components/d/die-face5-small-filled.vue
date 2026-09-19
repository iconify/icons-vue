<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0xll1iqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d0xll1iqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face5-small-filled" /></template>
