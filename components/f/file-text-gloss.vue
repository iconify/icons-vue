<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8wj3rsvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8wj3rsvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-text-gloss" /></template>
