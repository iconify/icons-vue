<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r48oh6fou.css';
import '../../css/n/nwovjeb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r48oh6fou"/><path class="nwovjeb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-link-open" /></template>
