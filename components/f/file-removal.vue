<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rixf5zbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rixf5zbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:file-removal" /></template>
