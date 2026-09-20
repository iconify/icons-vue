<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgm1b6z5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pgm1b6z5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:electrical-energy-filled" /></template>
