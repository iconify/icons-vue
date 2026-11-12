<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1a9__bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1a9__bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:brave-light" /></template>
