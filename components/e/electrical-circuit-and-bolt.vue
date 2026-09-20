<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gngkh0_1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gngkh0_1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:electrical-circuit-and-bolt" /></template>
