<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgxha5b3d.css';
import '../../css/x/xgliqgswb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgxha5b3d"/><path class="xgliqgswb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keyhelp" /></template>
