<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9hy2kbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9hy2kbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:campfire" /></template>
