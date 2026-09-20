<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjcbaabfa.css';
import '../../css/c/cgwih5znj.css';
import '../../css/c/cl_ajub-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zjcbaabfa"/><path class="cgwih5znj"/><path class="cl_ajub-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-backup-open" /></template>
