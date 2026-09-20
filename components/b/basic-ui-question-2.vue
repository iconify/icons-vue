<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9x6-5j_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q9x6-5j_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-question-2" /></template>
