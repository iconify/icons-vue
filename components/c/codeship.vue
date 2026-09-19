<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjq1h0isb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yjq1h0isb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:codeship" /></template>
