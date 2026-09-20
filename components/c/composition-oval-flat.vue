<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm7vcbbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lm7vcbbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:composition-oval-flat" /></template>
