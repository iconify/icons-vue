<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8l2z-7sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g8l2z-7sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad2-filled" /></template>
