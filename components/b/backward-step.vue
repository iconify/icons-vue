<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cutf4dd8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cutf4dd8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:backward-step" /></template>
