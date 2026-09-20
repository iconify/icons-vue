<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfrgf7bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tfrgf7bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cyberchef-light" /></template>
