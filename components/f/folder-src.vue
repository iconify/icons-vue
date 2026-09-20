<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz37bn_-f.css';
import '../../css/e/ejvzpugwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pz37bn_-f"/><path class="ejvzpugwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-src" /></template>
