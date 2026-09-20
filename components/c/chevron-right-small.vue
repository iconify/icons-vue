<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqgil-9zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqgil-9zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chevron-right-small" /></template>
