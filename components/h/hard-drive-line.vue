<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmvk0_a0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmvk0_a0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hard-drive-line" /></template>
