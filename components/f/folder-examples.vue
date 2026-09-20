<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufv-l2b0j.css';
import '../../css/a/aflrv12xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ufv-l2b0j"/><path class="aflrv12xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-examples" /></template>
