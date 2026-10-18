<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c01l0ubzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c01l0ubzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:eye-closed" /></template>
