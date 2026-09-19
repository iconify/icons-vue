<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvb7dyg7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvb7dyg7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:happy-heart-eyes-filled" /></template>
