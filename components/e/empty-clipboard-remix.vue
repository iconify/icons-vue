<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1s3auczn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o1s3auczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:empty-clipboard-remix" /></template>
