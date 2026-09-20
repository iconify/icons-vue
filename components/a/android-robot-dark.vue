<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrke2mbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xrke2mbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android-robot-dark" /></template>
