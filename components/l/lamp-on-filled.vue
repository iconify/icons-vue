<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft7_yqb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft7_yqb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lamp-on-filled" /></template>
