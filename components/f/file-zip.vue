<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anwcf1z6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="anwcf1z6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:file-zip" /></template>
