<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajrwfyblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ajrwfyblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chip" /></template>
