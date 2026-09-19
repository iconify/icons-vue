<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfezfgb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xfezfgb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dungeon" /></template>
