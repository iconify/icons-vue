<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqs-dvsfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nqs-dvsfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoicerr-light" /></template>
