<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/antgd2b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="antgd2b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:bot" /></template>
