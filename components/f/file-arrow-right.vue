<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o23fqybmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o23fqybmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-arrow-right" /></template>
