<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nht6o6bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nht6o6bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:fork" /></template>
