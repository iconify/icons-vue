<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqp0mzztf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hqp0mzztf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:journiv-light" /></template>
