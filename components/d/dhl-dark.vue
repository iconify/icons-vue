<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsbxedbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fsbxedbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dhl-dark" /></template>
