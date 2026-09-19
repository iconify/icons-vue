<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc4ubccba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nc4ubccba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-columns" /></template>
