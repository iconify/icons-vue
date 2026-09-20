<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enx00nbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enx00nbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-copy-fill" /></template>
