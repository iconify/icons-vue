<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpw8u2-_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpw8u2-_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heart-plus" /></template>
