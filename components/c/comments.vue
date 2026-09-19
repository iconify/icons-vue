<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp28btbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="xp28btbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comments" /></template>
