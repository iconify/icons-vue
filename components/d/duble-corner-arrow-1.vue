<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea-ko3b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ea-ko3b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:duble-corner-arrow-1" /></template>
