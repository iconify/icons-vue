<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkdog0g-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qkdog0g-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:error-compact" /></template>
