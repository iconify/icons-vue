<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbmu2dbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vbmu2dbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:linejoin-round-outline" /></template>
