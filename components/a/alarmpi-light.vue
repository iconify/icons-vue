<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkr2q8ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vkr2q8ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alarmpi-light" /></template>
