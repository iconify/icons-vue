<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw9rritcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw9rritcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-document-check" /></template>
