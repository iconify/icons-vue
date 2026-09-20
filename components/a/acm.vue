<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mllt-6bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mllt-6bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:acm" /></template>
