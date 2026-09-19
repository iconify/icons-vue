<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrjwqcqqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="xrjwqcqqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:devices-off" /></template>
