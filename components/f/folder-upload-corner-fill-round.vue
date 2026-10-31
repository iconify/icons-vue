<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thsueubkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thsueubkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-upload-corner-fill-round" /></template>
