<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnh_arkbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnh_arkbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:door-open-alt-filled" /></template>
