<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzazjq7mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzazjq7mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:link-unlink-m" /></template>
