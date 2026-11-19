<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3j1mmhwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3j1mmhwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:artcraft-light" /></template>
