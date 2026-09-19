<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj_94xbsg.css';
import '../../css/o/o_kremszb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj_94xbsg"/><path class="o_kremszb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:backpack-star" /></template>
