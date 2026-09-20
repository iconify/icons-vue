<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u48mzcbuj.css';
import '../../css/i/ijxvr0blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u48mzcbuj"/><path class="ijxvr0blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-constant-open" /></template>
