<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frdzy3b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frdzy3b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-mark-fill" /></template>
