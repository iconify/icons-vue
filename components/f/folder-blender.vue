<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbnjf8b6m.css';
import '../../css/h/hnt_a_4dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fbnjf8b6m"/><path class="hnt_a_4dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-blender" /></template>
