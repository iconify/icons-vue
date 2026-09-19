<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlx_pfbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rlx_pfbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:edit-page" /></template>
