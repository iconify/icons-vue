<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9ttlvb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ttlvb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-video-solid" /></template>
