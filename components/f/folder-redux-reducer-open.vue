<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhjw5tknw.css';
import '../../css/a/axvhkf15f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hhjw5tknw"/><path class="axvhkf15f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-redux-reducer-open" /></template>
