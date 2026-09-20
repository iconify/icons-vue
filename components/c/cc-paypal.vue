<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbrp9spkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sbrp9spkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-paypal" /></template>
