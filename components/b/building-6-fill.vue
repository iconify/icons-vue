<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf243ixuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wf243ixuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-6-fill" /></template>
