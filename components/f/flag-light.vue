<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xznkh2bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xznkh2bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:flag-light" /></template>
