<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6vurab3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h6vurab3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:caret-top" /></template>
