<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs8t_dbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs8t_dbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floppy-disc-edit-outline" /></template>
