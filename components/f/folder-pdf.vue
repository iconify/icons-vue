<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f95-ijf-n.css';
import '../../css/f/futrw6b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><path class="futrw6b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-pdf" /></template>
