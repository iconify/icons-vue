<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ien1wxbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ien1wxbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gamepad-star" /></template>
