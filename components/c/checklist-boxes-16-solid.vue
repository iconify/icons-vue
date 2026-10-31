<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdp6b9bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rdp6b9bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:checklist-boxes-16-solid" /></template>
