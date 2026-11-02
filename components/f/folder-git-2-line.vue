<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t30sd6bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t30sd6bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-git-2-line" /></template>
