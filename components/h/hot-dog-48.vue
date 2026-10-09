<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay0q9u-4z.css';
import '../../css/q/q4-w0wbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ay0q9u-4z"/><path class="q4-w0wbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-dog-48" /></template>
