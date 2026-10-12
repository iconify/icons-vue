<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuaejacgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuaejacgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:drafting-compass-filled" /></template>
