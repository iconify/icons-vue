<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4wi18b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4wi18b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-spreadsheet-plus" /></template>
