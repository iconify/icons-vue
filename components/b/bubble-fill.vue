<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otor3t_ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otor3t_ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bubble-fill" /></template>
