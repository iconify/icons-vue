<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1zalobua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="z1zalobua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-disconnect-compact" /></template>
