<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx91mjkwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx91mjkwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-pencil" /></template>
