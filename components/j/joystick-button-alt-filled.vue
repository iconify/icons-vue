<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lewgvx2df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lewgvx2df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:joystick-button-alt-filled" /></template>
