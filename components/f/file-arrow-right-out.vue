<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8veo69iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u8veo69iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-arrow-right-out" /></template>
