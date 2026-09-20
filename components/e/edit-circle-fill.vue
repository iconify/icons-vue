<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3_wibcqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3_wibcqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:edit-circle-fill" /></template>
