<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4goevt4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g4goevt4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ifanr-cloud" /></template>
