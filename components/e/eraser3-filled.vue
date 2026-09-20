<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugd28mosf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugd28mosf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eraser3-filled" /></template>
