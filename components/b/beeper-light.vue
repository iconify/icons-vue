<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymx_-ubor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymx_-ubor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beeper-light" /></template>
