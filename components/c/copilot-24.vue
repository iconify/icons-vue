<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnmcfvtyh.css';
import '../../css/a/axqd7-lja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnmcfvtyh"/><path class="axqd7-lja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:copilot-24" /></template>
