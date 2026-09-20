<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdiqizb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kdiqizb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:link-off" /></template>
