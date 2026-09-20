<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nth2z_w3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nth2z_w3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:android" /></template>
