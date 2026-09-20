<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri0479btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri0479btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bank-card-fill" /></template>
