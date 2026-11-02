<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m35kljbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m35kljbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-2-fill" /></template>
