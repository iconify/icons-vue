<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osf5v3bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="osf5v3bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cake-candles" /></template>
