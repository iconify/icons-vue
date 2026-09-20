<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obf1m3bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="obf1m3bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-diagonal-bottom-right" /></template>
