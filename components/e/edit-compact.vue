<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4pbix25t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="h4pbix25t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:edit-compact" /></template>
