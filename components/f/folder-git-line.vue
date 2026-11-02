<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pil_10b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pil_10b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-git-line" /></template>
