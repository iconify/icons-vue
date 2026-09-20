<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l11fmibpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":140,"height":140};
const content = `<path class="l11fmibpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:browserlist" /></template>
