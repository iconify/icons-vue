<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoyumsw5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoyumsw5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrow-left" /></template>
