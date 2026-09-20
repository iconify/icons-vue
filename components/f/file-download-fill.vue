<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g30601bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g30601bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-download-fill" /></template>
