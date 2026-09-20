<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg5ymdb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="fg5ymdb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gps-filled" /></template>
