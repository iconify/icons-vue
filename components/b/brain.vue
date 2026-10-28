<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efmf53bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efmf53bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:brain" /></template>
