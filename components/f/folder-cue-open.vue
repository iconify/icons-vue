<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hha2vm2py.css';
import '../../css/b/bz8x9x0cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hha2vm2py"/><path class="bz8x9x0cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cue-open" /></template>
