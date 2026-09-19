<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da0vyfbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da0vyfbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-joystick-alt" /></template>
