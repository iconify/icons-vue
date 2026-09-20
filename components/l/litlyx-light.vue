<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eluck1b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eluck1b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:litlyx-light" /></template>
