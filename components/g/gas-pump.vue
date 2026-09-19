<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2tz1nbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2tz1nbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:gas-pump" /></template>
