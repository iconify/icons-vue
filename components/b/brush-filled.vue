<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym7ozqbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym7ozqbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:brush-filled" /></template>
