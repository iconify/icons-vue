<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqh16pv3v.css';
import '../../css/u/u2z5ne2ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yqh16pv3v"/><path class="u2z5ne2ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-other" /></template>
