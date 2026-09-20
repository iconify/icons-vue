<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c35jjbcci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c35jjbcci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:anticlockwise-2-line" /></template>
