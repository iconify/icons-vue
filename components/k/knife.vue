<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp8_idbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cp8_idbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:knife" /></template>
