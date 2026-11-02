<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxa1-4b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxa1-4b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hard-drive-upload-fill" /></template>
