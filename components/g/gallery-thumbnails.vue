<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1h9_fb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1h9_fb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gallery-thumbnails" /></template>
