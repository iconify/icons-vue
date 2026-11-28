<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izz6ghbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izz6ghbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-code-lock" /></template>
