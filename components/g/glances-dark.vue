<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxbapv4lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxbapv4lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glances-dark" /></template>
