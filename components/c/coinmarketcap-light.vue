<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy1olh6cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy1olh6cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coinmarketcap-light" /></template>
