<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im0dkrbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im0dkrbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left5" /></template>
