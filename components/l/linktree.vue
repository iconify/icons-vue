<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4e783_3e.css';
import '../../css/v/vq5z-rl-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4e783_3e"/><path class="vq5z-rl-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:linktree" /></template>
