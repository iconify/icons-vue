<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr0iznzbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wr0iznzbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:brave-dark" /></template>
