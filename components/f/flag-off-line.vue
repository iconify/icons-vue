<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n047vkb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n047vkb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flag-off-line" /></template>
