<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmxj07brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmxj07brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ghstats-light" /></template>
