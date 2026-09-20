<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy76p--eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy76p--eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:lock-access" /></template>
