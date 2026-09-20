<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8x_9lbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8x_9lbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:growchief-light" /></template>
