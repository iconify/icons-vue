<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8bblxhcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="w8bblxhcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:label-alt-outline" /></template>
