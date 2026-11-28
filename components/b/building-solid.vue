<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1j6fbb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1j6fbb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:building-solid" /></template>
