<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buvlx_r8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buvlx_r8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:layers" /></template>
