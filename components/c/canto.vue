<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc50uobxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc50uobxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:canto" /></template>
