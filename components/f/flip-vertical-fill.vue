<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm5nsnb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm5nsnb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flip-vertical-fill" /></template>
