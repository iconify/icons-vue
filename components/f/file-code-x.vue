<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0cw-wb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0cw-wb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-code-x" /></template>
