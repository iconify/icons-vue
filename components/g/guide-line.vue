<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8o03pl8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8o03pl8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:guide-line" /></template>
