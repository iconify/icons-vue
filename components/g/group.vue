<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw3k0x4xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vw3k0x4xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:group" /></template>
