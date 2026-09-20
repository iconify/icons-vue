<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw7ny4b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bw7ny4b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-edit-spark-remix" /></template>
