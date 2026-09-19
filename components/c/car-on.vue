<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbfiudb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fbfiudb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:car-on" /></template>
