<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv4hdlb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zv4hdlb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emulatorjs-light" /></template>
