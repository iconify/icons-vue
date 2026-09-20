<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sexsn3bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sexsn3bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:cafe-14" /></template>
