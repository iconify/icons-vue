<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mic8vxb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mic8vxb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fastmail-dark" /></template>
