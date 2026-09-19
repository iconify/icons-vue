<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h451a74tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h451a74tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-circle-half" /></template>
