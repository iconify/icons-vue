<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqgtzq2po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqgtzq2po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-minus-outline" /></template>
