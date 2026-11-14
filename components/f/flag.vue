<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrds7xb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrds7xb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:flag" /></template>
