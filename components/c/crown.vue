<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7xpl3bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7xpl3bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:crown" /></template>
