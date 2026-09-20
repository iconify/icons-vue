<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbxi8usrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tbxi8usrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:europris-light" /></template>
