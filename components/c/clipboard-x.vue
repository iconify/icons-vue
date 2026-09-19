<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p632omv3c.css';
import '../../css/p/pa14hnb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p632omv3c"/><path class="pa14hnb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clipboard-x" /></template>
