<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwq82hbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwq82hbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:download-box-1" /></template>
