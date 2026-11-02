<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/air_i_kdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="air_i_kdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-terminal-fill" /></template>
