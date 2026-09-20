<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgimn7bxc.css';
import '../../css/t/t0u4brujn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgimn7bxc"/><path class="t0u4brujn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunar" /></template>
