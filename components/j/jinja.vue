<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5-dmccnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b5-dmccnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:jinja" /></template>
