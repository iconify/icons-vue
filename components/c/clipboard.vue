<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc715-kwz.css';
import '../../css/b/bctv-cbto.css';
import '../../css/h/hustz32ji.css';
import '../../css/a/a55wzqn_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yc715-kwz"/><path class="bctv-cbto wm-k"/><path class="hustz32ji wm-a"/><path class="a55wzqn_l wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:clipboard" /></template>
