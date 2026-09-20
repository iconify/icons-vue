<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d42htuhxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="d42htuhxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-error-bar" /></template>
