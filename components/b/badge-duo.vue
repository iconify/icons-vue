<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psxbs1bui.css';
import '../../css/h/haywxnunw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psxbs1bui secondary"/><path class="haywxnunw primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-duo" /></template>
