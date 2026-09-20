<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4uiyxbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4uiyxbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:contactless-payment-circle-outline" /></template>
