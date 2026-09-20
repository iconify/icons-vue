<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-k-7gbvo.css';
import '../../css/i/ivnpqujhz.css';
import '../../css/s/sps4d_myo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-k-7gbvo"/><path class="ivnpqujhz"/><path class="sps4d_myo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:calendar-grid" /></template>
