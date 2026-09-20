<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdbshfbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdbshfbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-keyhole-line" /></template>
