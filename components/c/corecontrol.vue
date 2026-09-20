<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so50nvbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="so50nvbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:corecontrol" /></template>
