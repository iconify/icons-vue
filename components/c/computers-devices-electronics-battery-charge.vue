<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk6bicnte.css';
import '../../css/d/dh6tuqe-f.css';
import '../../css/t/tjb6i-jcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lk6bicnte"/><path class="dh6tuqe-f"/><path class="tjb6i-jcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-battery-charge" /></template>
