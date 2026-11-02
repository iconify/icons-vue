<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc_wzy_-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc_wzy_-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmarks-line" /></template>
