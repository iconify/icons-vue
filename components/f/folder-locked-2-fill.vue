<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqec9l1pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqec9l1pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-locked-2-fill" /></template>
