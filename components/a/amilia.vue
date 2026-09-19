<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fffub0b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fffub0b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:amilia" /></template>
