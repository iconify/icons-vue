<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l65irgbeq.css';
import '../../css/f/fl6g1hb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l65irgbeq"/><path class="fl6g1hb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:headplane-light" /></template>
