<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye4aqbkod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye4aqbkod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-code-fill" /></template>
