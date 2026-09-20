<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft95ixbdo.css';
import '../../css/h/hw6ek8bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft95ixbdo"/><path class="hw6ek8bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:crypto-currency-bitcoin-dollar-exchange-bold" /></template>
