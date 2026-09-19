<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw5g0xbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yw5g0xbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrows-alt" /></template>
