<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtt8v1bcn.css';
import '../../css/h/h2cw1srdy.css';
import '../../css/o/o_4o-hjdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rtt8v1bcn"/><path class="h2cw1srdy"/><path class="o_4o-hjdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crew-transfer-vessel-20-bold" /></template>
