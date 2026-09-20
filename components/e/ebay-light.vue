<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfm92hrvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfm92hrvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ebay-light" /></template>
