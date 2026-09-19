<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzmvx9hyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzmvx9hyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:faucet" /></template>
