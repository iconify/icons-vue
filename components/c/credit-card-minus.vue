<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccgk95bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccgk95bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:credit-card-minus" /></template>
