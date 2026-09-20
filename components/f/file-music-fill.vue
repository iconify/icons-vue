<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y297yhbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y297yhbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-music-fill" /></template>
