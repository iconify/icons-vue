<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3xx_lb7w.css';
import '../../css/r/rosvxu7bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m3xx_lb7w"/><path class="rosvxu7bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-off-filled" /></template>
