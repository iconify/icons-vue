<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx_ljtb_m.css';
import '../../css/z/za3i1qbft.css';
import '../../css/o/o5jhy_bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kx_ljtb_m"/><path class="za3i1qbft"/><path class="o5jhy_bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flashlight-20-bold" /></template>
