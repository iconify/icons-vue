<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwejal1aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xwejal1aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grayjay-dark" /></template>
