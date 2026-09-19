<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3d3babjk.css';
import '../../css/o/owcw62b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3d3babjk"/><path class="owcw62b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hand-rock-filled" /></template>
