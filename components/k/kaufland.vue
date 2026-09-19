<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb1dfs46w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xb1dfs46w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:kaufland" /></template>
