<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enk2i125f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="enk2i125f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-document-fill-16" /></template>
