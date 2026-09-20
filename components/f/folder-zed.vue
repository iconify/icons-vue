<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thk9tudjp.css';
import '../../css/n/ni5juab4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thk9tudjp"/><path class="ni5juab4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-zed" /></template>
