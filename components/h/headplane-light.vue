<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l65irgbeq.css';
import '../../css/h/h-ks45b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l65irgbeq"/><path class="h-ks45b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headplane-light" /></template>
