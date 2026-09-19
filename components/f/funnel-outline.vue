<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnjxj5bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bnjxj5bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:funnel-outline" /></template>
