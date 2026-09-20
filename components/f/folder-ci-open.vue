<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8r7eptda.css';
import '../../css/u/u1tsesnyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u8r7eptda"/><path class="u1tsesnyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-ci-open" /></template>
