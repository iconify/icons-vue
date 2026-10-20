<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlkz-3bot.css';
import '../../css/x/x5r2fk28b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlkz-3bot"/><path class="x5r2fk28b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coupon-48" /></template>
