<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzh5w72co.css';
import '../../css/k/kgcox8b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tzh5w72co"/><path class="kgcox8b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-ios-open" /></template>
