<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvktx1bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvktx1bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-off" /></template>
