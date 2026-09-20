<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne__3rynp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne__3rynp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:download-1-filled" /></template>
