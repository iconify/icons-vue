<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f95-ijf-n.css';
import '../../css/f/fxny2_b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><path class="fxny2_b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-app" /></template>
