<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n03bg7bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n03bg7bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:joystick-01" /></template>
