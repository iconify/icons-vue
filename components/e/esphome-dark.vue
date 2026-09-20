<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz5434rjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mz5434rjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:esphome-dark" /></template>
