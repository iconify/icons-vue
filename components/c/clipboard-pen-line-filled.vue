<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu28debah.css';
import '../../css/d/divqy_2wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mu28debah"/><path class="divqy_2wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clipboard-pen-line-filled" /></template>
