<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbwzm5bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbwzm5bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-plus-line" /></template>
