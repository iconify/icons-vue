<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo4vm5lrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo4vm5lrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-upload" /></template>
