<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4-a0lh9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="d4-a0lh9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:compass" /></template>
