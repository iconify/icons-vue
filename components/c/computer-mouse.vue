<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx8wksbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="jx8wksbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:computer-mouse" /></template>
