<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmh1bfs7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmh1bfs7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dot-01-xs" /></template>
