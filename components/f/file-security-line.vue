<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap50jdwsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap50jdwsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-security-line" /></template>
