<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbhv8bbfx.css';
import '../../css/z/z_pgce4lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbhv8bbfx"/><path class="z_pgce4lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-left-stroke-circle-filled" /></template>
