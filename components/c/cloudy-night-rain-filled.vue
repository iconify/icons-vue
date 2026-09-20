<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml4h4gbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml4h4gbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cloudy-night-rain-filled" /></template>
