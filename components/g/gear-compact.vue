<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg7ralbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fg7ralbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:gear-compact" /></template>
