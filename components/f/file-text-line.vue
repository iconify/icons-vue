<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1ljo7brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ljo7brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-text-line" /></template>
