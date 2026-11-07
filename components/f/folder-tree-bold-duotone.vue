<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn8j1cc6q.css';
import '../../css/b/by22ydp5s.css';
import '../../css/q/quxmn86ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cn8j1cc6q"/><path class="by22ydp5s"/><path class="quxmn86ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-tree-bold-duotone" /></template>
