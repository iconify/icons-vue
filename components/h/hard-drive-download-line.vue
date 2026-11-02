<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3bmh4yvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3bmh4yvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hard-drive-download-line" /></template>
