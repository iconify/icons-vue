<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e75amibgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e75amibgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-merge-x" /></template>
