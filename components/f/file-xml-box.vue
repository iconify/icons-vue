<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbi9hljjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbi9hljjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-xml-box" /></template>
