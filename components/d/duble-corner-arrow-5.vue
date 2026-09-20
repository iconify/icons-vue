<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsd66bbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qsd66bbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:duble-corner-arrow-5" /></template>
