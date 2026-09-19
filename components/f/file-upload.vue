<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el5c7fldi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="el5c7fldi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-upload" /></template>
