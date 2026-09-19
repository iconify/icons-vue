<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao2hdcbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao2hdcbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:heading" /></template>
