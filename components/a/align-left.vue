<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr-607bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wr-607bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:align-left" /></template>
