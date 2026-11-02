<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akud0m0pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akud0m0pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-check-fill" /></template>
