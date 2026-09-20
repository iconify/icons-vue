<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew_8hjs3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ew_8hjs3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:galaxy-2-remix" /></template>
