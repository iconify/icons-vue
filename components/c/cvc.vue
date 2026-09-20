<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhazzstms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhazzstms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cvc" /></template>
