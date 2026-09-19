<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1o8dn6qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="w1o8dn6qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:gif" /></template>
