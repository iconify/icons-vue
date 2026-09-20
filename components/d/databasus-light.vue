<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uon3nobpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uon3nobpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:databasus-light" /></template>
