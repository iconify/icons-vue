<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_vx9acpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_vx9acpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badges-off" /></template>
