<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmfle6btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmfle6btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apps-2-ai-line" /></template>
