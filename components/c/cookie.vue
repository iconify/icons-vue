<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qruyi9g6m.css';
import '../../css/k/k9qv75bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qruyi9g6m"/><path class="k9qv75bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cookie" /></template>
