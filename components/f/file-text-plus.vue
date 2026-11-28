<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u177z4tmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u177z4tmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-text-plus" /></template>
