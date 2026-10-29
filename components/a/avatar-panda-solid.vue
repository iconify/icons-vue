<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfdzy9bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfdzy9bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-panda-solid" /></template>
