<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxa-w1bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxa-w1bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-office-line" /></template>
