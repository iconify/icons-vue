<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj4pi6b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mj4pi6b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-folder-zip-zip-folder-compact" /></template>
