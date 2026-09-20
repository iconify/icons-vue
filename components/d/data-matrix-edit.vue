<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh0q2jb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh0q2jb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:data-matrix-edit" /></template>
