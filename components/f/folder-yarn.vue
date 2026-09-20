<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhg495fle.css';
import '../../css/z/zk3ynnbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nhg495fle"/><path class="zk3ynnbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-yarn" /></template>
