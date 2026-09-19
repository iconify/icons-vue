<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpdpv0b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="mpdpv0b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:car-side" /></template>
