<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe3u1kbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe3u1kbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-text-solid" /></template>
