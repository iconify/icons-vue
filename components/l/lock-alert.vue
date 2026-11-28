<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naza5tbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="naza5tbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lock-alert" /></template>
