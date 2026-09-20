<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0djsxb9c.css';
import '../../css/r/r6hbisqks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0djsxb9c"/><path class="r6hbisqks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-desktop-open" /></template>
