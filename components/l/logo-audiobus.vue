<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg08evbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cg08evbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:logo-audiobus" /></template>
