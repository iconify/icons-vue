<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_j4uacvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_j4uacvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bitstamp" /></template>
