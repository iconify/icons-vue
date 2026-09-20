<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pffnfbbjn.css';
import '../../css/e/ejvzpugwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pffnfbbjn"/><path class="ejvzpugwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-src-open" /></template>
