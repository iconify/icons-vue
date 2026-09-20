<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftl45_bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftl45_bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-box-multiple-outline" /></template>
