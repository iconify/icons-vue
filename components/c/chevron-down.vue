<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut5oznbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut5oznbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:chevron-down" /></template>
