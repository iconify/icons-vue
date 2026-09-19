<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/harom8_fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="harom8_fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:file-video-fill" /></template>
