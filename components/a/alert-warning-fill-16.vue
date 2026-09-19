<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgrlryu3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tgrlryu3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alert-warning-fill-16" /></template>
