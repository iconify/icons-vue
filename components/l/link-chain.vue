<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np1cm194g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="np1cm194g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:link-chain" /></template>
