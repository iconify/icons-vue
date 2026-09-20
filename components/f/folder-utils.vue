<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5evchskr.css';
import '../../css/q/qa0jhaboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a5evchskr"/><path class="qa0jhaboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-utils" /></template>
