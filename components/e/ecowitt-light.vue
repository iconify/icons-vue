<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oos9bsboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oos9bsboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ecowitt-light" /></template>
