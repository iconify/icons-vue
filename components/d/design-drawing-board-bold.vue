<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhjwiab9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhjwiab9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:design-drawing-board-bold" /></template>
