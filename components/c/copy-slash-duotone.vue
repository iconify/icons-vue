<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h_zqz4bcf.css';
import '../../css/y/ytv39-yuk.css';
import '../../css/x/xqtkfkc4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h_zqz4bcf"/><path class="ytv39-yuk"/><path class="xqtkfkc4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:copy-slash-duotone" /></template>
