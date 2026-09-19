<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh6orpnrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hh6orpnrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:glass-water" /></template>
