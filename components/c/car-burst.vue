<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfx04gw8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="wfx04gw8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:car-burst" /></template>
