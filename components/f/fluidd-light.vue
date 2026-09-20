<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifnc4e1_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ifnc4e1_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluidd-light" /></template>
