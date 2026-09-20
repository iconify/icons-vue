<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e35l8w-da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e35l8w-da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bridge-2-filled" /></template>
