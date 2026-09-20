<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-c3zb9h.css';
import '../../css/m/mexy6lbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v7-c3zb9h"/><path class="mexy6lbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gradle" /></template>
