<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwc177mig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwc177mig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x2" /></template>
