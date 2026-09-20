<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnur2xbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jnur2xbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:class-lesson-remix" /></template>
