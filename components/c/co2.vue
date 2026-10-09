<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkvy30bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkvy30bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:co2" /></template>
