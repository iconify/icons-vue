<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/naq0tfbis.css';
import '../../css/p/pkado8zjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="naq0tfbis"/><path class="pkado8zjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-sync" /></template>
