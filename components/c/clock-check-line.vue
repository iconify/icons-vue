<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvo6lw2-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvo6lw2-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-check-line" /></template>
