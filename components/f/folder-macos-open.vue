<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s27ky2-ij.css';
import '../../css/i/i2crm77yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s27ky2-ij"/><path class="i2crm77yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-macos-open" /></template>
