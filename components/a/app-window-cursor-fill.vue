<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxpc9z8vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxpc9z8vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-cursor-fill" /></template>
