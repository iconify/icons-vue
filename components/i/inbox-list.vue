<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s11k6bcsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s11k6bcsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:inbox-list" /></template>
