<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5zlxkrxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m5zlxkrxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-tape-cassette" /></template>
