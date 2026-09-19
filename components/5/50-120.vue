<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7qxp_zpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="w7qxp_zpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:50-120" /></template>
