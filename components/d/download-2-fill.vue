<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_9-f9blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_9-f9blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-2-fill" /></template>
