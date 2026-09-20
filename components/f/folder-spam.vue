<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueq_z4bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ueq_z4bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:folder-spam" /></template>
