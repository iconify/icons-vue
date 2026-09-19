<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm1g5qbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fm1g5qbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-left-to-line" /></template>
