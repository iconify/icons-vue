<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw2k4fb0y.css';
import '../../css/d/d5-tlybrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pw2k4fb0y"/><path class="d5-tlybrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:containerssh-light" /></template>
