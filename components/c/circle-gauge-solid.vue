<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9b6zdsnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9b6zdsnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-gauge-solid" /></template>
