<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkwreep6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xkwreep6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-up-left-20-solid" /></template>
