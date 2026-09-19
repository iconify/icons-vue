<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjf-xsbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xjf-xsbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:jetpackcompose-wordmark" /></template>
