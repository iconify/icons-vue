<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_f6sqfep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_f6sqfep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-commit-fill" /></template>
