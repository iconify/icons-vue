<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq0e7yb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq0e7yb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dumbbell-alt-filled" /></template>
