<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_wt6fb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_wt6fb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jwt-io-dark" /></template>
