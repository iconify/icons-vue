<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejdhsp1qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejdhsp1qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:computer-camera-off-line" /></template>
