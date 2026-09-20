<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu_x_zbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu_x_zbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:discorddotjs" /></template>
