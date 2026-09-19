<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6ccxni9z.css';
import '../../css/i/iz9zsdbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6ccxni9z"/><path class="iz9zsdbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-money-withdraw" /></template>
