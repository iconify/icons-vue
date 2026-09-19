<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbfi7hipm.css';
import '../../css/a/amdrwrbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="jbfi7hipm"/><path class="amdrwrbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:assembly" /></template>
