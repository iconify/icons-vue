<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxonjtbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxonjtbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:expand-arrows-alt" /></template>
