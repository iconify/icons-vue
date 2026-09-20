<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhwe4xbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhwe4xbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-plus" /></template>
