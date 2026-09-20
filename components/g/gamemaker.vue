<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afa8214vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="afa8214vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:gamemaker" /></template>
