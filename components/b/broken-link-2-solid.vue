<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrn7oxbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jrn7oxbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:broken-link-2-solid" /></template>
