<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz1up0bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="wz1up0bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-australia-o" /></template>
