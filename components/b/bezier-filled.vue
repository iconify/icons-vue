<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbm6x22ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbm6x22ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bezier-filled" /></template>
