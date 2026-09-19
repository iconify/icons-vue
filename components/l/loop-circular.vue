<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms9_73-iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms9_73-iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:loop-circular" /></template>
