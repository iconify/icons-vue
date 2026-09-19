<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9r4x3jzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e9r4x3jzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cook" /></template>
