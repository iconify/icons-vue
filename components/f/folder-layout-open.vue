<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0djsxb9c.css';
import '../../css/o/oytr_p5za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0djsxb9c"/><path class="oytr_p5za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-layout-open" /></template>
