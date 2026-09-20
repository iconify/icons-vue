<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeck0ilxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xeck0ilxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:double-quote-serif-right" /></template>
