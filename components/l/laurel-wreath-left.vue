<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj3otwbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj3otwbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laurel-wreath-left" /></template>
