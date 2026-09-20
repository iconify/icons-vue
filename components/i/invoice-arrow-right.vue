<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhb1mqwuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhb1mqwuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-arrow-right" /></template>
