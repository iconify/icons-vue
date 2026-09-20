<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipy5vwtjx.css';
import '../../css/d/d6guelbgt.css';
import '../../css/p/pyhrjesye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipy5vwtjx"/><path clip-rule="evenodd" class="d6guelbgt"/><path class="pyhrjesye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:icp" /></template>
