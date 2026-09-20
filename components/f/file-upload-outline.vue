<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jps7tfbgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jps7tfbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-upload-outline" /></template>
