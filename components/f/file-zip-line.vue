<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l61a34b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l61a34b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-zip-line" /></template>
