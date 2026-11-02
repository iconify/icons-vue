<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhfphl-pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhfphl-pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:exchange-bitcoin-2-fill" /></template>
