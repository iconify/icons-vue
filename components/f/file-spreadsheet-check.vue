<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/memeveb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="memeveb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-spreadsheet-check" /></template>
