<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd506yb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xd506yb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anonaddy-light" /></template>
