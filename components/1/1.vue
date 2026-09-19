<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9gwph64c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":175,"height":735};
const content = `<path class="e9gwph64c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:1" /></template>
