<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw44cqses.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw44cqses"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-candle-filled" /></template>
