<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg171ebhl.css';
import '../../css/u/uga_xo1ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hg171ebhl"/><path class="uga_xo1ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-assembly" /></template>
