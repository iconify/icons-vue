<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsrhq3bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qsrhq3bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bitcoin-circle" /></template>
