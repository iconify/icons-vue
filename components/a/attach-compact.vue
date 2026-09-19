<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzk5mpk7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nzk5mpk7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:attach-compact" /></template>
