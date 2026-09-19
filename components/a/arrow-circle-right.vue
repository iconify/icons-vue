<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa9uucfpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pa9uucfpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-circle-right" /></template>
