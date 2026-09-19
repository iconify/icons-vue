<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq1jtnbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xq1jtnbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:airplane-sharp" /></template>
