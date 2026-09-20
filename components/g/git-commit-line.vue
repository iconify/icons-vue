<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itz2mac9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itz2mac9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-commit-line" /></template>
