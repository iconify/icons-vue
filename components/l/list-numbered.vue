<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdo6aybas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdo6aybas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:list-numbered" /></template>
