<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi3v-fbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="qi3v-fbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-text" /></template>
