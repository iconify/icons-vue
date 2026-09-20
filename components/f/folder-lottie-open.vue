<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu9ugknqy.css';
import '../../css/d/dld45g65o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wu9ugknqy"/><path class="dld45g65o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-lottie-open" /></template>
