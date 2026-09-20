<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjzvqj5xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjzvqj5xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:invision-line" /></template>
