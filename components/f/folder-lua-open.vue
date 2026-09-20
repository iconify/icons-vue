<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l32lerbfx.css';
import '../../css/v/v-975mjhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l32lerbfx"/><path class="v-975mjhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-lua-open" /></template>
