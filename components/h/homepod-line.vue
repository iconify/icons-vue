<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsq92pz-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsq92pz-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:homepod-line" /></template>
