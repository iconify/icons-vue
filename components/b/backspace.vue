<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlr6cy_uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlr6cy_uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:backspace" /></template>
