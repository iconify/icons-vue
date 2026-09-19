<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdziatdzg.css';
import '../../css/r/r_w95gdro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdziatdzg"/><path class="r_w95gdro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-stroke-circle-half-filled" /></template>
