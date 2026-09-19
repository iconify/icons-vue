<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk01hl6-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk01hl6-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bath" /></template>
