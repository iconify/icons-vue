<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haf1n5bdl.css';
import '../../css/x/xtz1kbe1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="haf1n5bdl"/><path class="xtz1kbe1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-project-open" /></template>
