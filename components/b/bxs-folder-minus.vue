<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk3va7a2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk3va7a2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-folder-minus" /></template>
