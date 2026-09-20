<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts8chuoof.css';
import '../../css/h/hqufffsil.css';
import '../../css/v/ves5g3ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ts8chuoof"/><path class="hqufffsil"/><path class="ves5g3ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:karrot" /></template>
