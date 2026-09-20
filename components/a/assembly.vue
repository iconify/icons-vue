<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuelrk4mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kuelrk4mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:assembly" /></template>
