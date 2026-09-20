<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt8n-9b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jt8n-9b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-top-left-right" /></template>
