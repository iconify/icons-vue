<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_zxljbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_zxljbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bell-plus" /></template>
