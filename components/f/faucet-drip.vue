<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g728qbc4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g728qbc4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:faucet-drip" /></template>
