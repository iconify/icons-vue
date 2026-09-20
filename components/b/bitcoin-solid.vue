<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmft1cb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmft1cb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bitcoin-solid" /></template>
