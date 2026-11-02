<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg-n1kdas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg-n1kdas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-minus-fill" /></template>
