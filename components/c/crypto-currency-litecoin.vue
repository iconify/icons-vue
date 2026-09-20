<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcehwxpiv.css';
import '../../css/q/qs3nn1ykv.css';
import '../../css/o/o3v08d-1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcehwxpiv"/><path class="qs3nn1ykv"/><path class="o3v08d-1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:crypto-currency-litecoin" /></template>
