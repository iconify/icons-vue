<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc0vyvbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc0vyvbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:ferris-wheel" /></template>
