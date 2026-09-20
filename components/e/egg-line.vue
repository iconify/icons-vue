<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz-gipbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz-gipbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egg-line" /></template>
