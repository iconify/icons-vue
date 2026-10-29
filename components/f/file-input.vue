<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/v/vk4yonzaw.css';
import '../../css/p/p1kbumysc.css';
import '../../css/o/ozl2zbbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="vk4yonzaw"/><path class="p1kbumysc"/><path class="ozl2zbbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:file-input" /></template>
