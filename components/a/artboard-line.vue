<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg1tgxrkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg1tgxrkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:artboard-line" /></template>
