<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku34nyb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku34nyb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-drop-left-line" /></template>
