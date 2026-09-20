<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igpt2fgqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igpt2fgqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fullscreen-2" /></template>
