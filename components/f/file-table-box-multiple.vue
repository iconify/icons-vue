<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg3gzprxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg3gzprxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-table-box-multiple" /></template>
