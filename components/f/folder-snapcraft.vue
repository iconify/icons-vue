<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppoewyanq.css';
import '../../css/u/ungtlkbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ppoewyanq"/><path class="ungtlkbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-snapcraft" /></template>
