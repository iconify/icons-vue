<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl401gbue.css';
import '../../css/x/xjfts2dhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl401gbue"/><path class="xjfts2dhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cash-payment-bill-bold" /></template>
