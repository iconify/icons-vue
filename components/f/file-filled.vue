<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o794mi5kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o794mi5kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-filled" /></template>
