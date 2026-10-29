<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vynbphhpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vynbphhpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-image-solid" /></template>
