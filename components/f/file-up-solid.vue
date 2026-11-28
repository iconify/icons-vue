<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inkyztxvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inkyztxvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-up-solid" /></template>
