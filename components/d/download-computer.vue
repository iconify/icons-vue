<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8bzgz7vs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b8bzgz7vs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:download-computer" /></template>
