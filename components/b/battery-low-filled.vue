<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8w49wgny.css';
import '../../css/f/fdgucpbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8w49wgny"/><path class="fdgucpbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:battery-low-filled" /></template>
