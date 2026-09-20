<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6cjc0bct.css';
import '../../css/q/qrs0kj75x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v6cjc0bct"/><path class="qrs0kj75x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-middleware" /></template>
