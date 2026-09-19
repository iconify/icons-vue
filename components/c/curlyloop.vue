<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqp8abb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqp8abb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:curlyloop" /></template>
