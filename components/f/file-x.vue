<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg_s41kyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg_s41kyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-x" /></template>
