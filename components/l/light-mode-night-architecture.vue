<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9-ij8bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b9-ij8bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:light-mode-night-architecture" /></template>
