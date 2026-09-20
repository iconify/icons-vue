<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qysbv0mly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qysbv0mly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bluetooth-light" /></template>
