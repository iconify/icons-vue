<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9l3diuic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9l3diuic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:file-upload-filled" /></template>
