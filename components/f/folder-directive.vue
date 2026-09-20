<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajw-j-mwd.css';
import '../../css/q/q-anz_blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ajw-j-mwd"/><path class="q-anz_blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-directive" /></template>
