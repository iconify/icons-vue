<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fco4h-r_s.css';
import '../../css/l/ljjk5bimi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fco4h-r_s"/><path class="ljjk5bimi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:cashless-payment-qr-code-basket-bold" /></template>
