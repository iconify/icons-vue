<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xny50ibfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xny50ibfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ergo-dark" /></template>
