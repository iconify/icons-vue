<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wct_gyo-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wct_gyo-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:confetti2-filled" /></template>
