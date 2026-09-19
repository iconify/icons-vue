<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y568x_bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="y568x_bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:dot-circle" /></template>
