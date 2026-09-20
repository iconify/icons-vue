<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz4v91hwj.css';
import '../../css/l/lhr648d7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gz4v91hwj"/><path class="lhr648d7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cursor-light" /></template>
