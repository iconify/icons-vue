<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik5l8_l-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ik5l8_l-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:data-board" /></template>
