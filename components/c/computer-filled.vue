<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f33j-7cos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b f33j-7cos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:computer-filled" /></template>
