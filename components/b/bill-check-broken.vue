<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/opk43_ukr.css';
import '../../css/z/z8b6ep4dx.css';
import '../../css/q/qrqz59bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="opk43_ukr"/><path class="z8b6ep4dx"/><path class="qrqz59bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-check-broken" /></template>
