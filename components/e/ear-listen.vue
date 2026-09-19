<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlt5h_mac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dlt5h_mac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ear-listen" /></template>
