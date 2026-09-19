<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqih-abzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqih-abzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:color-wheel" /></template>
