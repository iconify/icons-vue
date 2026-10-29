<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwvmuh2tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwvmuh2tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-circle-solid" /></template>
