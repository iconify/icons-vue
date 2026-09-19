<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg-d_yb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg-d_yb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chevron-up-square" /></template>
