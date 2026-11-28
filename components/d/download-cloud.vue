<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bng7-4bni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bng7-4bni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:download-cloud" /></template>
