<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so61k4u2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so61k4u2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bath-filled" /></template>
