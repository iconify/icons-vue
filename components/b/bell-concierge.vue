<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn7_n2bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cn7_n2bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bell-concierge" /></template>
