<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdty62s8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bdty62s8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:arrow-up" /></template>
