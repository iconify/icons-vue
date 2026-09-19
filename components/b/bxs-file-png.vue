<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-ok2sbil.css';
import '../../css/d/dosvuyafw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-ok2sbil"/><path class="dosvuyafw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-png" /></template>
