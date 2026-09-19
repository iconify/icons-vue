<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8b0e2b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e8b0e2b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:code-slash-sharp" /></template>
