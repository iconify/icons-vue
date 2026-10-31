<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxkgrdb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxkgrdb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-edit-corner-round" /></template>
