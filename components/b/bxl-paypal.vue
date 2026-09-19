<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9_s-nbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9_s-nbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-paypal" /></template>
