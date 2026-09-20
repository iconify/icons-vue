<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in4fcbbhz.css';
import '../../css/d/dellb70ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in4fcbbhz"/><path class="dellb70ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:funkwhale" /></template>
