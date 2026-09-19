<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clywwkbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clywwkbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:angle-filled" /></template>
