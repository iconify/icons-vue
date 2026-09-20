<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aprx8ebqb.css';
import '../../css/i/i3h3u4txt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aprx8ebqb"/><path class="i3h3u4txt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-helm-open" /></template>
