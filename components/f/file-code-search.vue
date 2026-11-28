<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3h0-u43f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3h0-u43f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-code-search" /></template>
