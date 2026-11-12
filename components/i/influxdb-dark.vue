<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wup54xb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wup54xb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:influxdb-dark" /></template>
