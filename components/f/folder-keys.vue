<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l47nr7bbh.css';
import '../../css/i/iywcnqb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l47nr7bbh"/><path class="iywcnqb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-keys" /></template>
