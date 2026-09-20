<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v69s4zcsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v69s4zcsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:google-wallet" /></template>
