<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvgy20fzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvgy20fzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hoopla" /></template>
