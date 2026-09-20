<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws370un0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ws370un0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:hand" /></template>
