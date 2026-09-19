<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuyhfknlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="uuyhfknlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-photo-o" /></template>
