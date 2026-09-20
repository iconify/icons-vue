<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8gqn_bfy.css';
import '../../css/u/uxjr5m63m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q8gqn_bfy"/><path class="uxjr5m63m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-controller-open" /></template>
