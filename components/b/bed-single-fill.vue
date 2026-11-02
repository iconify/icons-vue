<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za_4knwjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za_4knwjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bed-single-fill" /></template>
