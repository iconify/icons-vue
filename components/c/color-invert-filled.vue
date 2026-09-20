<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjtd81bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjtd81bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:color-invert-filled" /></template>
