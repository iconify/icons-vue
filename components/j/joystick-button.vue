<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdh4qvbdd.css';
import '../../css/z/zb9ioj-fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdh4qvbdd"/><path class="zb9ioj-fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:joystick-button" /></template>
