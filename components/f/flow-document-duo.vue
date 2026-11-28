<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4qsytige.css';
import '../../css/i/i3jzowbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4qsytige secondary"/><path class="i3jzowbmb primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-document-duo" /></template>
