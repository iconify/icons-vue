<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6yqnk6da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h6yqnk6da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:document-edit" /></template>
