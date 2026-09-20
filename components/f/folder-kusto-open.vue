<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haf1n5bdl.css';
import '../../css/o/oxa9fqbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="haf1n5bdl"/><path class="oxa9fqbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-kusto-open" /></template>
