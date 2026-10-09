<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh7k9xbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eh7k9xbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clouds-48" /></template>
