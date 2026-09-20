<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iem4vkb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iem4vkb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit-2-fill" /></template>
