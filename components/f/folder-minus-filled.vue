<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e94cj6bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e94cj6bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-minus-filled" /></template>
