<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv3fxhbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv3fxhbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-fill" /></template>
