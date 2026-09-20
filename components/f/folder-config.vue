<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd1yx_bjk.css';
import '../../css/h/htfzp21pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kd1yx_bjk"/><path class="htfzp21pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-config" /></template>
