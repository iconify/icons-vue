<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhjw5tknw.css';
import '../../css/a/a98ziyr1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hhjw5tknw"/><path class="a98ziyr1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-scons-open" /></template>
