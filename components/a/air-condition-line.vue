<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn4b8bcbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn4b8bcbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-condition-line" /></template>
