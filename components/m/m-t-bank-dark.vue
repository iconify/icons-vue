<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwbp4q8dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fwbp4q8dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:m-t-bank-dark" /></template>
