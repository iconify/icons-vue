<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-qxuibhr.css';
import '../../css/y/y_4y_gbst.css';
import '../../css/d/dwj5ymbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-qxuibhr"/><path class="y_4y_gbst"/><path class="dwj5ymbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-vue-open" /></template>
