<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4lgz2bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g4lgz2bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:file-failed" /></template>
