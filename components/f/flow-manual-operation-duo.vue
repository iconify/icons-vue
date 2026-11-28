<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cna5h-bpn.css';
import '../../css/k/k5oixywsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cna5h-bpn secondary"/><path class="k5oixywsl primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-manual-operation-duo" /></template>
