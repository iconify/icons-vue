<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct2bdybif.css';
import '../../css/j/jh04-5upe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ct2bdybif"/><path class="jh04-5upe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-content" /></template>
