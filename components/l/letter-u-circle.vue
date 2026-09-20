<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kig0xacpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kig0xacpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-u-circle" /></template>
