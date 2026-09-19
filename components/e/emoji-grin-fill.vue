<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrkaw1ncp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wrkaw1ncp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-grin-fill" /></template>
