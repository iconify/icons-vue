<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg171ebhl.css';
import '../../css/z/z6ju0jldq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hg171ebhl"/><path class="z6ju0jldq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-postman" /></template>
