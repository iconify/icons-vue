<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqo5rw4pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tqo5rw4pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:alarm-clock-cancelled" /></template>
