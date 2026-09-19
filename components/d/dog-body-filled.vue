<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzv03fbgv.css';
import '../../css/k/kid6f5maa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzv03fbgv"/><path class="kid6f5maa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dog-body-filled" /></template>
