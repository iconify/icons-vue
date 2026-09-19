<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8nsyd_1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="j8nsyd_1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-powerpoint-o" /></template>
