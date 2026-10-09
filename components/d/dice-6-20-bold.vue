<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfgcicctr.css';
import '../../css/l/lnhu_cben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sfgcicctr"/><path class="lnhu_cben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-6-20-bold" /></template>
