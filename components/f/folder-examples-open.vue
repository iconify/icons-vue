<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzicu7o9n.css';
import '../../css/a/aflrv12xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jzicu7o9n"/><path class="aflrv12xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-examples-open" /></template>
