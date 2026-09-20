<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chhzk1bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="chhzk1bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:airpipe-dark" /></template>
