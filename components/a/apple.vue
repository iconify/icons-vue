<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wabtt1w3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":488};
const content = `<path class="wabtt1w3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:apple" /></template>
