<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af3h010ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af3h010ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diving-scuba-tank-multiple" /></template>
