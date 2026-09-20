<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk1sao3wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uk1sao3wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fresh-editor-dark" /></template>
