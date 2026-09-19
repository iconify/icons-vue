<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv4yr7owx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uv4yr7owx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:crystal-ball-filled" /></template>
