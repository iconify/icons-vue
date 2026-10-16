<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw9esif9u.css';
import '../../css/i/ikm4i4bwb.css';
import '../../css/s/s0mrvwbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sw9esif9u"/><path class="ikm4i4bwb"/><path class="s0mrvwbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-gauge-48-bold" /></template>
