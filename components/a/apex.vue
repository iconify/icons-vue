<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz58fnbwx.css';
import '../../css/x/x4shk053m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz58fnbwx"/><path class="x4shk053m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:apex" /></template>
