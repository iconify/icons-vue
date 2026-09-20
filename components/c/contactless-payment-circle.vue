<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra_a-eb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_a-eb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:contactless-payment-circle" /></template>
