<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhv9facqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhv9facqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:electrical-energy" /></template>
