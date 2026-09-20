<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d78kiv0is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d78kiv0is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:download-box-1-solid" /></template>
