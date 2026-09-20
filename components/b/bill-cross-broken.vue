<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uiwsg29tk.css';
import '../../css/q/qrqz59bvc.css';
import '../../css/o/opk43_ukr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uiwsg29tk"/><path class="qrqz59bvc"/><path class="opk43_ukr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-cross-broken" /></template>
