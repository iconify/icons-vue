<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aux3m8cjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aux3m8cjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:activity" /></template>
