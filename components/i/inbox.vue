<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypov33b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ypov33b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:inbox" /></template>
