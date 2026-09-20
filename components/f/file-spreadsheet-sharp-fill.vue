<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nseund19v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nseund19v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-spreadsheet-sharp-fill" /></template>
