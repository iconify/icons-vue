<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcxeust6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcxeust6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-round" /></template>
