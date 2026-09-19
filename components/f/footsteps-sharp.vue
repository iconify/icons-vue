<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umpd97b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="umpd97b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:footsteps-sharp" /></template>
