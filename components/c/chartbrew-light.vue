<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh-xzlbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hh-xzlbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chartbrew-light" /></template>
