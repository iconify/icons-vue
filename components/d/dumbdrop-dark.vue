<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0h-p-b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n0h-p-b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbdrop-dark" /></template>
