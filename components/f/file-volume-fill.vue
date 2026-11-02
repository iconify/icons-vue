<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v06f5ldfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v06f5ldfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-volume-fill" /></template>
