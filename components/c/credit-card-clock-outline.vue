<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc00k61ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc00k61ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-clock-outline" /></template>
