<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqrv59bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqrv59bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iobroker-dark" /></template>
