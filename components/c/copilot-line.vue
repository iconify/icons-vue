<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_1rzsb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_1rzsb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copilot-line" /></template>
