<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ammg21y8z.css';
import '../../css/g/glm6tvnou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ammg21y8z"/><path clip-rule="evenodd" class="glm6tvnou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:backhand-index-pointing-down-medium-light" /></template>
