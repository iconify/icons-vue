<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4w-vcsn.css';
import '../../css/n/nhqbeobkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ov4w-vcsn"/><path class="nhqbeobkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-debug-open" /></template>
