<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkb3d8iqr.css';
import '../../css/v/vxhny_5ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkb3d8iqr"/><path clip-rule="evenodd" class="vxhny_5ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:card-sim-filled" /></template>
