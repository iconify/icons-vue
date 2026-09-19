<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcv3dlbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcv3dlbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:joystick" /></template>
