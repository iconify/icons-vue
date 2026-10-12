<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv2urftea.css';
import '../../css/p/p03glfbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uv2urftea"/><path clip-rule="evenodd" class="p03glfbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:face-grinning-filled" /></template>
