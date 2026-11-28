<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guephn89g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guephn89g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:faucet-solid" /></template>
